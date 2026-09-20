<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw88lzjcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw88lzjcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-line" {...props}></Icon>
