<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thz6gtmay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thz6gtmay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-2-fill" {...props}></Icon>
