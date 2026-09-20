<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo0ilnblt.css';
import '../../css/p/pdeg3lb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo0ilnblt"/><path class="pdeg3lb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stargaze" {...props}></Icon>
