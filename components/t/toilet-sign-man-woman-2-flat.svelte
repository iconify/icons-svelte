<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvgr2srcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pvgr2srcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:toilet-sign-man-woman-2-flat" {...props}></Icon>
