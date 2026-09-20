<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdlu0hf_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdlu0hf_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:telegram-line" {...props}></Icon>
