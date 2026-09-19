<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-i-xmbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m-i-xmbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:taobao" {...props}></Icon>
