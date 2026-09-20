<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiw_u92lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fiw_u92lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:skull-1-solid" {...props}></Icon>
