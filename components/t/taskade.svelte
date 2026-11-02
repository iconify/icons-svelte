<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh5ame3kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dh5ame3kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:taskade" {...props}></Icon>
