<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6e1gm-ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c6e1gm-ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:trash" {...props}></Icon>
