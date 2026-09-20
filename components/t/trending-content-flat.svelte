<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xagi25i7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xagi25i7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:trending-content-flat" {...props}></Icon>
