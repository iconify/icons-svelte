<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz335zj5g.css';
import '../../css/u/ux2qx_n6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz335zj5g"/><path class="ux2qx_n6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:sound-on-solid" {...props}></Icon>
