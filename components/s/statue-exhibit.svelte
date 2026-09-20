<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr3hgeb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wr3hgeb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:statue-exhibit" {...props}></Icon>
