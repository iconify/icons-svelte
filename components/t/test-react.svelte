<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1sxc4bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1sxc4bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:test-react" {...props}></Icon>
