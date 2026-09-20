<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp_bqbcum.css';
import '../../css/s/s9t-vws4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vp_bqbcum"/><path class="s9t-vws4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sive" {...props}></Icon>
