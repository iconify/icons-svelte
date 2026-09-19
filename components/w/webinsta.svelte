<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2vpy-vhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":771};
const content = `<path class="v2vpy-vhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:webinsta" {...props}></Icon>
