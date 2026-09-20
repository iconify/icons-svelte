<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no41bfb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no41bfb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-broken" {...props}></Icon>
