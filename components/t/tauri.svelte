<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqhp__bzd.css';
import '../../css/o/oqawcacrr.css';
import '../../css/b/bwplvcc-j.css';
import '../../css/r/rcxx25bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vqhp__bzd"/><path class="oqawcacrr"/><path class="bwplvcc-j"/><path class="rcxx25bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tauri" {...props}></Icon>
