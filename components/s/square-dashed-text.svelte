<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_l8wibur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_l8wibur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-dashed-text" {...props}></Icon>
