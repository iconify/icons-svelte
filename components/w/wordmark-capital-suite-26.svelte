<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu29ecc4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":52,"height":26};
const content = `<path class="nu29ecc4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-capital-suite-26" {...props}></Icon>
