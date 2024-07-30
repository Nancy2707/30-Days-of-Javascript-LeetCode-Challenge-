
Array.prototype.groupBy = function(fn) {
    const grouped = {};
    for (const item of this) {
        const key = fn(item);
        if (!grouped[key]) {
            grouped[key] = [];
        }
        grouped[key].push(item);
    }

    return grouped;
};
