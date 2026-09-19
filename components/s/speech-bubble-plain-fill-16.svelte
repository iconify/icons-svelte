<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqgo5iwmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nqgo5iwmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-plain-fill-16" {...props}></Icon>
