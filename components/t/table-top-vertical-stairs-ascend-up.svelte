<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxm_88f5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fxm_88f5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-vertical-stairs-ascend-up" {...props}></Icon>
