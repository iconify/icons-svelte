<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzw6u4r6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qzw6u4r6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signage-4-solid" {...props}></Icon>
