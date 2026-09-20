<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4dft0rcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4dft0rcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:snow-flake" {...props}></Icon>
