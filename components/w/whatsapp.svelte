<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9h3x8vab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9h3x8vab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:whatsapp" {...props}></Icon>
