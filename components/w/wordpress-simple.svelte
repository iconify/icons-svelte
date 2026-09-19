<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdus9ldpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jdus9ldpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:wordpress-simple" {...props}></Icon>
