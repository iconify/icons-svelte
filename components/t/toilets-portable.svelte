<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adcwh5bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="adcwh5bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:toilets-portable" {...props}></Icon>
