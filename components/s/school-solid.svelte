<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzmqqjpen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tzmqqjpen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:school-solid" {...props}></Icon>
