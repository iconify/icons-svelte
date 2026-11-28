<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v13iy5dkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v13iy5dkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sticky-note" {...props}></Icon>
