<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqahxcbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqahxcbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:settings-alt-fill-round" {...props}></Icon>
