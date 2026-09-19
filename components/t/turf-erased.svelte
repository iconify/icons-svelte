<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9i1vdbko.css';
import '../../css/o/oakyvybig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f9i1vdbko"/><path class="oakyvybig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-erased" {...props}></Icon>
