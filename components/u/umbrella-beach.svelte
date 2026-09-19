<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqohm2nbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="uqohm2nbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:umbrella-beach" {...props}></Icon>
