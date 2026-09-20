<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/uk_v7bife.css';
import '../../css/b/b1w3ycbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="h01tyzbfu"><path class="uk_v7bife"/><path class="b1w3ycbdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:slack" {...props}></Icon>
