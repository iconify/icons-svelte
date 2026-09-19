<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mqsny_bib.css';
import '../../css/b/b14jacbag.css';
import '../../css/v/vlpjmacdk.css';
import '../../css/p/pz5dn8bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mqsny_bib"/><path class="b14jacbag"/><path clip-rule="evenodd" class="vlpjmacdk"/><path class="pz5dn8bel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-amount-up-outline" {...props}></Icon>
