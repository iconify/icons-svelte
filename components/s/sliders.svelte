<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahb2qab2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ahb2qab2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sliders" {...props}></Icon>
