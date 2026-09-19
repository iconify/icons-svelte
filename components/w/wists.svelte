<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf1_q-baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":472};
const content = `<path class="yf1_q-baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:wists" {...props}></Icon>
