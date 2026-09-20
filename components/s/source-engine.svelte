<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k98pe1uop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k98pe1uop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:source-engine" {...props}></Icon>
