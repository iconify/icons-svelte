<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgd5zucvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgd5zucvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:slash-square" {...props}></Icon>
