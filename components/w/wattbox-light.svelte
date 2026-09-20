<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwg8tgbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwg8tgbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wattbox-light" {...props}></Icon>
