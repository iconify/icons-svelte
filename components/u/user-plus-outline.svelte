<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy_oq0bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yy_oq0bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:user-plus-outline" {...props}></Icon>
