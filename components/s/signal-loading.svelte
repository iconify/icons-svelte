<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9vru-sib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="h9vru-sib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-loading" {...props}></Icon>
