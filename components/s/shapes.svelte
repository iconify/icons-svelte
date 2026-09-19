<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od9a5k13f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="od9a5k13f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shapes" {...props}></Icon>
