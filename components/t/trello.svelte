<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0jn04mof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="i0jn04mof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:trello" {...props}></Icon>
