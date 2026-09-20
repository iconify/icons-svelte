<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2k5pjb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s2k5pjb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:subtract-square" {...props}></Icon>
