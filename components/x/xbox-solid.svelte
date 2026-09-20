<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrbsh4b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yrbsh4b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:xbox-solid" {...props}></Icon>
