<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvrzfbc7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bvrzfbc7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sharealt" {...props}></Icon>
