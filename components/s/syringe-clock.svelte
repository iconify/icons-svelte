<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4sppcdxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4sppcdxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:syringe-clock" {...props}></Icon>
