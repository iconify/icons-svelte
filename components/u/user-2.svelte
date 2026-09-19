<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evc_qlbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evc_qlbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:user-2" {...props}></Icon>
