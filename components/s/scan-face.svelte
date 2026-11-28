<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io1bjgbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io1bjgbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scan-face" {...props}></Icon>
