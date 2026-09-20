<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyjqt4buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gyjqt4buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:taobao" {...props}></Icon>
