<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgjs0nvgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qgjs0nvgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-slash" {...props}></Icon>
