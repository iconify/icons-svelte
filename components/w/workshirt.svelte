<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esmh27b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="esmh27b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:workshirt" {...props}></Icon>
