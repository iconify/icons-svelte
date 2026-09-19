<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e984jd2wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e984jd2wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shield-fill-exclamation" {...props}></Icon>
