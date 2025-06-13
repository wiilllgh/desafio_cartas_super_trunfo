# desafio_cartas_super_trunfo
Desafio Estácio

int main() {

    //variáveis para a PRIMEIRA carta
    char codigo_carta_1[4]; //ex: A01
    int populacao_1;
    float area_1;
    float pib_1;
    int pontos_turisticos_1;

    //variáveis para a SEGUNDA carta
    char codigo_carta_2[4]; //ex: B02
    int populacao_2;
    float area_2;
    float pib_2;
    int pontos_turisticos_2;

    printf("Cadastro da PRIMEIRA Carta\n");

    printf("Digite o codigo da carta (ex: A01): ");
    scanf("%s", codigo_carta_1);

    printf("Digite a populacao: ");
    scanf("%d", &populacao_1);

    printf("Digite a area (em km2): ");
    scanf("%f", &area_1);

    printf("Digite o PIB (em bilhoes): ");
    scanf("%f", &pib_1);

    printf("Digite o numero de pontos turisticos: ");
    scanf("%d", &pontos_turisticos_1);

    printf("\nCadastro da SEGUNDA Carta\n");

    printf("Digite o codigo da carta (ex: B02): ");
    scanf("%s", codigo_carta_2);

    printf("Digite a populacao: ");
    scanf("%d", &populacao_2);

    printf("Digite a area (em km2): ");
    scanf("%f", &area_2);

    printf("Digite o PIB (em bilhoes): ");
    scanf("%f", &pib_2);

    printf("Digite o numero de pontos turisticos: ");
    scanf("%d", &pontos_turisticos_2);

    printf("\nDados das Cartas Cadastradas\n");

    printf("\nCarta: %s\n", codigo_carta_1);
    printf("Populacao: %d\n", populacao_1);
    printf("Area: %.2f km2\n", area_1);
    printf("PIB: %.2f bilhoes\n", pib_1);
    printf("Pontos Turisticos: %d\n", pontos_turisticos_1);

    printf("\nCarta: %s\n", codigo_carta_2);
    printf("Populacao: %d\n", populacao_2);
    printf("Area: %.2f km2\n", area_2);
    printf("PIB: %.2f bilhoes\n", pib_2);
    printf("Pontos Turisticos: %d\n", pontos_turisticos_2);

    return 0;
}
