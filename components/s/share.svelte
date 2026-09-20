<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am_i4l4_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am_i4l4_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:share" {...props}></Icon>
