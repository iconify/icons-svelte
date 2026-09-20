<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh5eilbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kh5eilbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:web-check-light" {...props}></Icon>
