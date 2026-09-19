<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2mh2_bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t2mh2_bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:router-voice" {...props}></Icon>
