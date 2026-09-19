<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7lh-6b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z7lh-6b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:start" {...props}></Icon>
