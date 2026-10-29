<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_new4w6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_new4w6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:signal-solid" {...props}></Icon>
