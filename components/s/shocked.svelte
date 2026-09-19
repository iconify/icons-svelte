<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayrvy6blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayrvy6blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shocked" {...props}></Icon>
