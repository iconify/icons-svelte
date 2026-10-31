<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i850hdcmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i850hdcmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tooth-round" {...props}></Icon>
