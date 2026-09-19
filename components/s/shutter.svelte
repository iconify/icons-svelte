<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnsns6ogg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnsns6ogg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shutter" {...props}></Icon>
