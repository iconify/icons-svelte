<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw2fmneoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1472};
const content = `<path class="pw2fmneoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:user-waiter-female" {...props}></Icon>
