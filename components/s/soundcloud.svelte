<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqbt5cble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":622};
const content = `<path class="pqbt5cble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:soundcloud" {...props}></Icon>
