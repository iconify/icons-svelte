<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b06mc9r6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="b06mc9r6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:rupee-sign" {...props}></Icon>
