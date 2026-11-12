<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymrr6abhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymrr6abhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yabin-light" {...props}></Icon>
