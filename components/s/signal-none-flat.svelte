<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twl58-cvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="twl58-cvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:signal-none-flat" {...props}></Icon>
