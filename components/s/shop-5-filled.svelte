<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfnxo0etm.css';
import '../../css/j/jb-34lb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfnxo0etm"/><path class="jb-34lb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:shop-5-filled" {...props}></Icon>
