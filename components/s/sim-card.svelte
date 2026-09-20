<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyb_2jbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jyb_2jbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sim-card" {...props}></Icon>
