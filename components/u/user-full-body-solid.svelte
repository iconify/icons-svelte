<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw_x16bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uw_x16bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:user-full-body-solid" {...props}></Icon>
