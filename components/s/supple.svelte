<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd1o0wddx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qd1o0wddx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:supple" {...props}></Icon>
