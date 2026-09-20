<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnxtpfsch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnxtpfsch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:save-fill" {...props}></Icon>
