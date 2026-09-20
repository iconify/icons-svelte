<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftfnlwbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftfnlwbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:yahoo" {...props}></Icon>
