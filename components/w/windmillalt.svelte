<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot7aftx3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1025};
const content = `<path class="ot7aftx3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:windmillalt" {...props}></Icon>
