<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg4w-xbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":512};
const content = `<path class="wg4w-xbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:virtualbox" {...props}></Icon>
