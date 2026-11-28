<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx3y4h7cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx3y4h7cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:zoom-in" {...props}></Icon>
