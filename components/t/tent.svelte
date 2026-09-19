<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-et5mbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="g-et5mbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tent" {...props}></Icon>
