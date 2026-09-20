<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/degat7bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="degat7bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:suitcase-rolling-solid" {...props}></Icon>
