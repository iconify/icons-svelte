<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb9gv9bqr.css';
import '../../css/j/jw-5zob1j.css';
import '../../css/l/l2nzezbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sb9gv9bqr"/><path class="jw-5zob1j"/><path class="l2nzezbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stethoscope-20-bold" {...props}></Icon>
