<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_ud-v2xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p_ud-v2xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:vine" {...props}></Icon>
