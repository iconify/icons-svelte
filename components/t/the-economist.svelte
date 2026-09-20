<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx4b6zb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":250,"height":127.556};
const content = `<path class="wx4b6zb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-economist" {...props}></Icon>
