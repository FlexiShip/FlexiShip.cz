    <div className="min-h-screen bg-gray-100 p-6">
      <div className="max-w-4xl mx-auto text-center">
        <h1 className="text-4xl font-bold text-gray-900 mb-4">Profesionální balení a expedice pro e-shopy</h1>
        <p className="text-lg text-gray-700 mb-6">
          Outsourcujte balení a expedici objednávek a ušetřete čas i náklady.
        </p>
        <Button className="bg-red-500 hover:bg-red-600 text-white px-6 py-3 rounded-lg text-lg">
          Kontaktovat nás
        </Button>
      </div>

      <div className="grid grid-cols-1 md:grid-cols-2 gap-6 mt-10 max-w-4xl mx-auto">
        <Card>
          <CardContent className="p-6">
            <CheckCircle className="text-green-500 w-10 h-10 mb-3" />
            <h2 className="text-xl font-semibold mb-2">Rychlé a efektivní balení</h2>
            <p className="text-gray-600">Zabalíme vaše objednávky pečlivě a efektivně – už od 10 Kč za balík.</p>
          </CardContent>
        </Card>
        
        <Card>
          <CardContent className="p-6">
            <CheckCircle className="text-green-500 w-10 h-10 mb-3" />
            <h2 className="text-xl font-semibold mb-2">Možnost skladování</h2>
            <p className="text-gray-600">Vaše produkty můžeme skladovat za výhodných podmínek.</p>
          </CardContent>
        </Card>
      </div>

      <div className="max-w-4xl mx-auto text-center mt-12">
        <h2 className="text-3xl font-bold text-gray-900 mb-4">Ceník služeb</h2>
        <p className="text-lg text-gray-700 mb-6">Transparentní a férové ceny:</p>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-6">
          <Card>
            <CardContent className="p-6">
              <h3 className="text-xl font-semibold mb-2">Balení malých zásilek</h3>
              <p className="text-gray-600">od 10 Kč / ks</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6">
              <h3 className="text-xl font-semibold mb-2">Balení větších zásilek</h3>
              <p className="text-gray-600">od 15 Kč / ks</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6">
              <h3 className="text-xl font-semibold mb-2">Skladování</h3>
              <p className="text-gray-600">od 500 Kč / měsíc</p>
            </CardContent>
          </Card>
        </div>
      </div>

      <div className="text-center mt-12">
        <Button className="bg-red-500 hover:bg-red-600 text-white px-6 py-3 rounded-lg text-lg">
          Požádat o nabídku
        </Button>
      </div>
    </div>
  );
}
