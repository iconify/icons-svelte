<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9aoccb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9aoccb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:save-solid" {...props}></Icon>
