<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvzclybtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvzclybtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sob-fill" {...props}></Icon>
