<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc5qjjbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="pc5qjjbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sound-down" {...props}></Icon>
