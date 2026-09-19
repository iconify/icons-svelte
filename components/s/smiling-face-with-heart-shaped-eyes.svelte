<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz9vf6d5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gz9vf6d5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:smiling-face-with-heart-shaped-eyes" {...props}></Icon>
