<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drc198znd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="drc198znd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:shield-2-flat" {...props}></Icon>
