<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-e-1ibqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n-e-1ibqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-eye-filled" {...props}></Icon>
