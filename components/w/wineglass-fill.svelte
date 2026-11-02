<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsbll9bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsbll9bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wineglass-fill" {...props}></Icon>
