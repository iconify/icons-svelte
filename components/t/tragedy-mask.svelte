<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-dh7vbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e-dh7vbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:tragedy-mask" {...props}></Icon>
