<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq_btub1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq_btub1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:trowel" {...props}></Icon>
