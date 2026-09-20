<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqg43f7sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lqg43f7sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sad-tear" {...props}></Icon>
