<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy8ud43tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xy8ud43tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:text-wrap" {...props}></Icon>
