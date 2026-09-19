<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaeie20lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eaeie20lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:shovel" {...props}></Icon>
