<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd400g6hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qd400g6hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:shield-halved" {...props}></Icon>
