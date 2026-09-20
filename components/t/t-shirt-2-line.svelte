<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okothmo9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okothmo9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:t-shirt-2-line" {...props}></Icon>
