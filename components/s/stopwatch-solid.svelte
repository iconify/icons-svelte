<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oni7yqb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oni7yqb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stopwatch-solid" {...props}></Icon>
