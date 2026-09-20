<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtx181bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtx181bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:spinner" {...props}></Icon>
