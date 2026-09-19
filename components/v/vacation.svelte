<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/vjqi9gboy.css';
import '../../css/w/wrqafjrbc.css';
import '../../css/b/bun8441ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="vjqi9gboy"/><path class="wrqafjrbc"/><path class="bun8441ri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:vacation" {...props}></Icon>
