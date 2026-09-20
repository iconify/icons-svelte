<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze4gsqcqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ze4gsqcqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:vim" {...props}></Icon>
