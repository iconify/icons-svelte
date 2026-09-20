<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e30mndklf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e30mndklf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-circle-filled" {...props}></Icon>
