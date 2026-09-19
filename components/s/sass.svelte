<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn8mvjb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zn8mvjb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sass" {...props}></Icon>
