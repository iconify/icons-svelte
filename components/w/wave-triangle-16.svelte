<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx-eucbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yx-eucbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wave-triangle-16" {...props}></Icon>
