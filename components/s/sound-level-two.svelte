<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clpvn6bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":472};
const content = `<path class="clpvn6bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sound-level-two" {...props}></Icon>
