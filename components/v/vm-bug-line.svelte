<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fovsdldng.css';
import '../../css/n/nt694ol2t.css';
import '../../css/s/sx-8igbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<rect class="fovsdldng"/><path class="nt694ol2t"/><path class="sx-8igbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:vm-bug-line" {...props}></Icon>
