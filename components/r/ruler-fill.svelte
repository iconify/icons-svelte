<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzkm-3f9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzkm-3f9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ruler-fill" {...props}></Icon>
