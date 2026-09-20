<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sndyfeb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sndyfeb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:stop" {...props}></Icon>
