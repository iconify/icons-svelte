<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/m84lw8bft.css';
import '../../css/e/eq8_rgx0j.css';
import '../../css/f/fryp0s66n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="m84lw8bft"/><circle class="eq8_rgx0j"/><circle class="fryp0s66n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:viencharts" {...props}></Icon>
