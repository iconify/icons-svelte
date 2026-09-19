<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4x3kxgfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f4x3kxgfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:thor" {...props}></Icon>
