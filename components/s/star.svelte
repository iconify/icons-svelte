<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iarsg9_lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iarsg9_lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:star" {...props}></Icon>
