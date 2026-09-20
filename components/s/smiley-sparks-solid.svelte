<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk0zk7bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zk0zk7bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-sparks-solid" {...props}></Icon>
