<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4dw0qbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v4dw0qbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:wget" {...props}></Icon>
