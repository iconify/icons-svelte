<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc_8i2kot.css';
import '../../css/c/cljz3cbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mc_8i2kot"/><path clip-rule="evenodd" class="cljz3cbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:server-16-solid" {...props}></Icon>
