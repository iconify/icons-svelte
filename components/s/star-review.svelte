<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbv6tsbiz.css';
import '../../css/w/wtstr4z9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hbv6tsbiz"/><path class="wtstr4z9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:star-review" {...props}></Icon>
