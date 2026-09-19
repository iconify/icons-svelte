<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j71l87b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j71l87b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:save2-fill" {...props}></Icon>
