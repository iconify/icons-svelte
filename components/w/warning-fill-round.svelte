<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlgb3ob_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlgb3ob_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:warning-fill-round" {...props}></Icon>
