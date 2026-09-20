<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_gzhippd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="e_gzhippd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:zap" {...props}></Icon>
