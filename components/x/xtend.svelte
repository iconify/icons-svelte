<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwr78-bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nwr78-bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:xtend" {...props}></Icon>
