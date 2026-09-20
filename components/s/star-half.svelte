<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfs0h1b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfs0h1b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:star-half" {...props}></Icon>
