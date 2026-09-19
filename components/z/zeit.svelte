<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8z5tcckk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8z5tcckk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:zeit" {...props}></Icon>
