<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khb354thf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khb354thf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:ruler-2-line" {...props}></Icon>
