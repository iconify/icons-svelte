<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjvn8-bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjvn8-bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tag-2-line" {...props}></Icon>
