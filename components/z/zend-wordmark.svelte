<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7gk3cces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u7gk3cces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:zend-wordmark" {...props}></Icon>
