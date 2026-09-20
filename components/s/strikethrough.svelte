<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wao5n55nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wao5n55nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:strikethrough" {...props}></Icon>
