<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcvn6yb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="kcvn6yb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:trophy" {...props}></Icon>
