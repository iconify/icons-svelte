<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsek8xbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fsek8xbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:user-minus-outline" {...props}></Icon>
