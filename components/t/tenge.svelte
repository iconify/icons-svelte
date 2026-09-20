<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3k7eu14g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x3k7eu14g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tenge" {...props}></Icon>
