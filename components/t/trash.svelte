<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnv7bpbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bnv7bpbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:trash" {...props}></Icon>
