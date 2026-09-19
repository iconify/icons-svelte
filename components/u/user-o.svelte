<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb3s7_7hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="bb3s7_7hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:user-o" {...props}></Icon>
