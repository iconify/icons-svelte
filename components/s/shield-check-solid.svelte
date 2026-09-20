<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym11dybwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ym11dybwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shield-check-solid" {...props}></Icon>
