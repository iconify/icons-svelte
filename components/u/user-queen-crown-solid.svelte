<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb5mtv2gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cb5mtv2gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:user-queen-crown-solid" {...props}></Icon>
