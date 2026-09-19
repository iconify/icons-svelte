<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt6tz56sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="xt6tz56sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:text-color" {...props}></Icon>
