<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-n2j-byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-n2j-byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:university" {...props}></Icon>
