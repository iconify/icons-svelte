<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwwvo3b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gwwvo3b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:square-caret-down" {...props}></Icon>
