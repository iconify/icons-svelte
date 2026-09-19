<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psh9t9-yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="psh9t9-yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-bars-vertical" {...props}></Icon>
