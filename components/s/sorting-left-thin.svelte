<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0bc2ytbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0bc2ytbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sorting-left-thin" {...props}></Icon>
