<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5df1egve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v5df1egve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:speech-bubbles-rtl" {...props}></Icon>
