<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc9p_p96d.css';
import '../../css/d/dti_o-b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zc9p_p96d"/><path class="dti_o-b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:theme-16" {...props}></Icon>
