<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rktgnbb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rktgnbb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:wix" {...props}></Icon>
