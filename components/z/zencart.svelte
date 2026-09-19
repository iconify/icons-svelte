<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrqj4ib2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vrqj4ib2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zencart" {...props}></Icon>
