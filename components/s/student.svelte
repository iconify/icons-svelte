<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axeen7-9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="axeen7-9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:student" {...props}></Icon>
