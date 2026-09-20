<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn25p6lzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn25p6lzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:volume-up-line" {...props}></Icon>
