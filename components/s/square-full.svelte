<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2ns6tbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k2ns6tbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:square-full" {...props}></Icon>
