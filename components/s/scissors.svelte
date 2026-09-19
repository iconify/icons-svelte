<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkv4lj3ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="vkv4lj3ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:scissors" {...props}></Icon>
