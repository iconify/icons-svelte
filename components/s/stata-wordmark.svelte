<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c195baxyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c195baxyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stata-wordmark" {...props}></Icon>
