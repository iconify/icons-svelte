<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecbzrebfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ecbzrebfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:sym-difference" {...props}></Icon>
