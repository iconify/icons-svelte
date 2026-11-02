<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdrlq8twt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdrlq8twt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:upload-fill" {...props}></Icon>
