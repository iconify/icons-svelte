<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr51um7au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kr51um7au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:share2" {...props}></Icon>
