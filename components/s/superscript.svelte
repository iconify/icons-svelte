<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5l55k5vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="q5l55k5vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:superscript" {...props}></Icon>
