<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc85rwl1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc85rwl1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:zodiac-gemini" {...props}></Icon>
