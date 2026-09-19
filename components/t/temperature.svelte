<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahdpb2baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="ahdpb2baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:temperature" {...props}></Icon>
