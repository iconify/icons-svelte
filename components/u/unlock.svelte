<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ockyt989s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1408};
const content = `<path class="ockyt989s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:unlock" {...props}></Icon>
