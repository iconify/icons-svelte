<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_gh4btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-_gh4btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:textile" {...props}></Icon>
