<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikp2_-bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ikp2_-bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sahibinden" {...props}></Icon>
