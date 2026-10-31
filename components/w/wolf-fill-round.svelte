<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlu1beb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlu1beb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wolf-fill-round" {...props}></Icon>
