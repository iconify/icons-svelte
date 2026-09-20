<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq6ae5uin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cq6ae5uin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tea-cup-solid" {...props}></Icon>
