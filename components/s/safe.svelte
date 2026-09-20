<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uakfjcbyb.css';
import '../../css/s/spxxfgbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uakfjcbyb"/><path class="spxxfgbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:safe" {...props}></Icon>
