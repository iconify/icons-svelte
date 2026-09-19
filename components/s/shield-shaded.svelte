<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhn1_ob-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lhn1_ob-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shield-shaded" {...props}></Icon>
