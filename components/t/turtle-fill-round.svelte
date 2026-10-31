<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxqij-tjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxqij-tjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:turtle-fill-round" {...props}></Icon>
