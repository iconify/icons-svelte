<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1fac2bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="m1fac2bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:times-circle-o" {...props}></Icon>
