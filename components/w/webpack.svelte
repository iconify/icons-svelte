<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn_i5xb7j.css';
import '../../css/t/tgvy-8bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bn_i5xb7j"/><path class="tgvy-8bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:webpack" {...props}></Icon>
