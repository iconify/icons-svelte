<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3bgbdlao.css';
import '../../css/l/ldp-e91yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a3bgbdlao"/><path class="ldp-e91yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:svelte-wordmark" {...props}></Icon>
