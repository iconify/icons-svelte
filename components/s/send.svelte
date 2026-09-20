<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df35pablj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="df35pablj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:send" {...props}></Icon>
