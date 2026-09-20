<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-6a3v2fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-6a3v2fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone" {...props}></Icon>
