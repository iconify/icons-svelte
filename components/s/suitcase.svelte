<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9u58f8ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i9u58f8ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:suitcase" {...props}></Icon>
