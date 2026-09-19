<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q94r-_bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q94r-_bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:warning" {...props}></Icon>
