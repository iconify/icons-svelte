<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r097kdbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r097kdbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:yang" {...props}></Icon>
