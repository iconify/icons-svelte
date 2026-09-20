<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbj5q2eai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbj5q2eai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:share" {...props}></Icon>
