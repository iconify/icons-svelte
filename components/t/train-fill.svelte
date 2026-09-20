<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqnvo5brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqnvo5brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:train-fill" {...props}></Icon>
