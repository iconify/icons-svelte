<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkd5ofbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkd5ofbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:zorinos" {...props}></Icon>
