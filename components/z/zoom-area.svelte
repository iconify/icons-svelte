<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmdltob3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qmdltob3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zoom-area" {...props}></Icon>
