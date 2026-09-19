<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5wakvbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":447,"height":512};
const content = `<path class="l5wakvbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rubygems" {...props}></Icon>
