<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhtp61rru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1792};
const content = `<path class="rhtp61rru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sun-o" {...props}></Icon>
