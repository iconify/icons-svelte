<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo9-9w_yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eo9-9w_yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:trophy-solid" {...props}></Icon>
