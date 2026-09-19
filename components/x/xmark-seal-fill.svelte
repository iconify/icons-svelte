<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmb40b8ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nmb40b8ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:xmark-seal-fill" {...props}></Icon>
