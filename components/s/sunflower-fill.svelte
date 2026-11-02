<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tar_hac0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tar_hac0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sunflower-fill" {...props}></Icon>
