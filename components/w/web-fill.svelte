<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym5qnl2lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym5qnl2lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:web-fill" {...props}></Icon>
