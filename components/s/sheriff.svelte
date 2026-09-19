<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/karqscbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="karqscbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sheriff" {...props}></Icon>
