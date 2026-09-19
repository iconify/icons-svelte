<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du109jbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="du109jbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sky-panorama" {...props}></Icon>
