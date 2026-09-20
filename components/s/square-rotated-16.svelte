<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6mqt5ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oj6mqt5ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:square-rotated-16" {...props}></Icon>
