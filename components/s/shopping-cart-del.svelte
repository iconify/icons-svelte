<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fx319o55e.css';
import '../../css/n/n148kwbte.css';
import '../../css/d/d8dbn7bpp.css';
import '../../css/i/igkx63b1j.css';
import '../../css/s/smax-acvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="fx319o55e"/><path class="n148kwbte"/><circle class="d8dbn7bpp"/><circle class="igkx63b1j"/><path class="smax-acvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:shopping-cart-del" {...props}></Icon>
