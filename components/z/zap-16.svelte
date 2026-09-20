<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxy23kbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cxy23kbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:zap-16" {...props}></Icon>
