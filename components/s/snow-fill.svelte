<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4gy4ccxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4gy4ccxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snow-fill" {...props}></Icon>
