<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzthrzbpn.css';
import '../../css/z/zvjeae8vn.css';
import '../../css/t/tdqgqzbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uzthrzbpn"/><path clip-rule="evenodd" class="zvjeae8vn"/><path class="tdqgqzbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ui-panels-left-right-16" {...props}></Icon>
