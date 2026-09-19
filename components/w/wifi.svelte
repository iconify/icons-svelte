<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3nhzub_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="g3nhzub_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:wifi" {...props}></Icon>
