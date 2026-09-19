<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l11k1yqcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l11k1yqcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:share" {...props}></Icon>
