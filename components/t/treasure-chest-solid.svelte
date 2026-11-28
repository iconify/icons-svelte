<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnvytvbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnvytvbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:treasure-chest-solid" {...props}></Icon>
