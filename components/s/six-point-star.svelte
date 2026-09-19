<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df88n9bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="df88n9bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:six-point-star" {...props}></Icon>
