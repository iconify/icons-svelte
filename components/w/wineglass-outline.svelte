<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clc8j0pcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="clc8j0pcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wineglass-outline" {...props}></Icon>
