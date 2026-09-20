<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot0ib_b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ot0ib_b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:volleyball-11" {...props}></Icon>
