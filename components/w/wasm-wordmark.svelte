<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqpr9y_fs.css';
import '../../css/y/ytq_a7bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nqpr9y_fs"/><path class="ytq_a7bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:wasm-wordmark" {...props}></Icon>
