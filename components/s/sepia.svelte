<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1iipibae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":712};
const content = `<path class="h1iipibae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:sepia" {...props}></Icon>
