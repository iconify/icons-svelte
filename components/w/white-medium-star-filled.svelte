<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx6x8mb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hx6x8mb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-medium-star-filled" {...props}></Icon>
