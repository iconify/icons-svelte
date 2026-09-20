<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etf4rgbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="etf4rgbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:user-feedback-heart-solid" {...props}></Icon>
