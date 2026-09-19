<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjq7bibqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jjq7bibqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:triangle-right-solid" {...props}></Icon>
