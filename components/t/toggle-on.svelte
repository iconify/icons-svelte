<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdc_jgbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="bdc_jgbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:toggle-on" {...props}></Icon>
