<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr43l9aex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mr43l9aex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:staroff" {...props}></Icon>
