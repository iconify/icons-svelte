<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p179t_bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p179t_bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:toggle-right-round" {...props}></Icon>
