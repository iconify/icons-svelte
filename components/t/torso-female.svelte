<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae2brcc5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ae2brcc5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:torso-female" {...props}></Icon>
