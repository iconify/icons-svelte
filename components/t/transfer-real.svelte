<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp90ugwwx.css';
import '../../css/x/xli4t7b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pp90ugwwx"/><path class="xli4t7b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:transfer-real" {...props}></Icon>
