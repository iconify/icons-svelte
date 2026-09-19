<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9zew8b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2560,"height":1472};
const content = `<path class="x9zew8b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:table-question" {...props}></Icon>
