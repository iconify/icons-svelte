<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2kaq6blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s2kaq6blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:upload-box-1-solid" {...props}></Icon>
