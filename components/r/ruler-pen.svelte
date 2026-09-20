<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u62_66b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="u62_66b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ruler-pen" {...props}></Icon>
