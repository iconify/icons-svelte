<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnyr25b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnyr25b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:send-cancel" {...props}></Icon>
