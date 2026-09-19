<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsz4ihbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dsz4ihbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:viruses" {...props}></Icon>
