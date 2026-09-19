<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtlw-ooxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dtlw-ooxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:turing" {...props}></Icon>
