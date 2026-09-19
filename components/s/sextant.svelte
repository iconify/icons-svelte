<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm4edqt9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sm4edqt9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sextant" {...props}></Icon>
