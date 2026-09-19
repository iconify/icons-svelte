<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amlvptyan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="amlvptyan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:unlock" {...props}></Icon>
