<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1jhk9bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v1jhk9bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:video-off-2" {...props}></Icon>
