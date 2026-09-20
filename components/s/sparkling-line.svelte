<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8yholbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8yholbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sparkling-line" {...props}></Icon>
