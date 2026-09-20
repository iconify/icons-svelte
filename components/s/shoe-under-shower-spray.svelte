<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsc-4-bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jsc-4-bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shoe-under-shower-spray" {...props}></Icon>
