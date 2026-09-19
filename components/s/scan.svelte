<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr5k4eg8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mr5k4eg8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:scan" {...props}></Icon>
