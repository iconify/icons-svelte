<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg-h_4-0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="eg-h_4-0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:success-multiple" {...props}></Icon>
