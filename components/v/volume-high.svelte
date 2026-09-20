<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikzj6qbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikzj6qbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:volume-high" {...props}></Icon>
