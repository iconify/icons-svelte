<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orbkw0iwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="orbkw0iwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:xmark-circle-fill" {...props}></Icon>
