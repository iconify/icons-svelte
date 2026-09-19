<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4vs8xdmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="y4vs8xdmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:vial" {...props}></Icon>
