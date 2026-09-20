<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkzz6m3te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkzz6m3te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shield" {...props}></Icon>
