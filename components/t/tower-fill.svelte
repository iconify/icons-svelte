<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr44ffbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr44ffbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-fill" {...props}></Icon>
