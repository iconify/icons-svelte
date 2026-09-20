<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upm3vqb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="upm3vqb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-cloud-sun-fine" {...props}></Icon>
