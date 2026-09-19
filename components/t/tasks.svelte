<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xey_w_xxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="xey_w_xxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tasks" {...props}></Icon>
