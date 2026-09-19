<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdzjbckde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vdzjbckde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:tileset" {...props}></Icon>
