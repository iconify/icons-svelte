<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnck5obfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnck5obfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:stroller-parking" {...props}></Icon>
