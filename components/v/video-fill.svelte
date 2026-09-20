<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egouyzdsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egouyzdsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-fill" {...props}></Icon>
