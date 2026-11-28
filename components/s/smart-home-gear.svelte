<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jctd3-bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jctd3-bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smart-home-gear" {...props}></Icon>
