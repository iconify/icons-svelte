<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-p1mk66q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q-p1mk66q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:snowplow" {...props}></Icon>
