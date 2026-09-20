<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scn_amr7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="scn_amr7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water" {...props}></Icon>
