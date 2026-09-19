<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0b5mabvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0b5mabvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:spark" {...props}></Icon>
