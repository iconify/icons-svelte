<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af-zpmbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af-zpmbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:windows-24" {...props}></Icon>
