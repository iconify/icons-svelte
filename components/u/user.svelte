<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs47dhnyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xs47dhnyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:user" {...props}></Icon>
