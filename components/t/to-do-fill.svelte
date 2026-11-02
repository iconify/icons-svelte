<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-jy4_bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-jy4_bfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:to-do-fill" {...props}></Icon>
