<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyfj8kb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yyfj8kb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:xmpp" {...props}></Icon>
