<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3pri2b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p3pri2b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:star-badge-solid" {...props}></Icon>
