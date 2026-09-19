<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_mvxfbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j_mvxfbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-follow-fill-16" {...props}></Icon>
