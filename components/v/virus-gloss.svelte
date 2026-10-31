<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me-uzgbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me-uzgbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:virus-gloss" {...props}></Icon>
