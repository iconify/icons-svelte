<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi41d3bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi41d3bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:syringe-round" {...props}></Icon>
