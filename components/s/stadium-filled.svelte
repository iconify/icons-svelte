<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3rv6zb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3rv6zb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:stadium-filled" {...props}></Icon>
