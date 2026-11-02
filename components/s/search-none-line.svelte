<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi3j7bcjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi3j7bcjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-none-line" {...props}></Icon>
