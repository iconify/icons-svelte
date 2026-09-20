<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkh7o7b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vkh7o7b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voux-light" {...props}></Icon>
