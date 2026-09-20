<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clk6xjb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clk6xjb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:t-shirt-linear" {...props}></Icon>
