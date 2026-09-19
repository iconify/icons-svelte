<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv8p9kb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iv8p9kb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:svelte-wordmark" {...props}></Icon>
