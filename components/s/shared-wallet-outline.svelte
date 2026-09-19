<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/p/pa8-l1l1b.css';
import '../../css/x/x0hbydb5g.css';
import '../../css/m/mimbgsbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="pa8-l1l1b"/><rect class="x0hbydb5g"/><path class="mimbgsbve"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:shared-wallet-outline" {...props}></Icon>
