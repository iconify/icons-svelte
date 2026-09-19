<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu0ey4b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu0ey4b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ruler-arrows" {...props}></Icon>
