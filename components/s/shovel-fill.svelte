<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k33suh6om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k33suh6om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shovel-fill" {...props}></Icon>
