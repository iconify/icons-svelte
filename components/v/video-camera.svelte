<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lym7mzbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lym7mzbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:video-camera" {...props}></Icon>
