<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkd6frbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vkd6frbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sails" {...props}></Icon>
