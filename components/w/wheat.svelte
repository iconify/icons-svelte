<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxq73bs4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxq73bs4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wheat" {...props}></Icon>
