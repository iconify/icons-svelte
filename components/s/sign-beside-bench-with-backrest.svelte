<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eahhtsb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eahhtsb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sign-beside-bench-with-backrest" {...props}></Icon>
