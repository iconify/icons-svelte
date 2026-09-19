<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo49c-7rn.css';
import '../../css/e/ev1e0nbdz.css';
import '../../css/y/yiwzwpb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wo49c-7rn"/><path class="ev1e0nbdz"/><path class="yiwzwpb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:speak" {...props}></Icon>
