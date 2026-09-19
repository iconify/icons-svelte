<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm325hbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm325hbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shapes" {...props}></Icon>
