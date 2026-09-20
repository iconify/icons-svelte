<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/furm6vb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="furm6vb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:spray" {...props}></Icon>
