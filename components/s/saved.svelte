<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1jtovu1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m1jtovu1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:saved" {...props}></Icon>
