<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhx6pibvk.css';
import '../../css/b/b1w3ycbdv.css';
import '../../css/u/uk_v7bife.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="mhx6pibvk"><path class="b1w3ycbdv"/><path class="uk_v7bife"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:slack" {...props}></Icon>
