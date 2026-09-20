<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqdup5oyd.css';
import '../../css/a/a3yzckbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="bqdup5oyd"/><path class="a3yzckbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:thunder" {...props}></Icon>
