<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otlkl261z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="otlkl261z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:router" {...props}></Icon>
