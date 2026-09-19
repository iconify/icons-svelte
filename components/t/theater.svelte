<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyyaptw9m.css';
import '../../css/g/g2y0sfb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hyyaptw9m"/><path class="g2y0sfb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:theater" {...props}></Icon>
