<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj305obcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vj305obcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:wind" {...props}></Icon>
