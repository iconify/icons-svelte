<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r29iocc1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r29iocc1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sofa-heart" {...props}></Icon>
