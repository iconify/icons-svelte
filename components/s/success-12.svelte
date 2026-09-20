<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svsuljcxx.css';
import '../../css/c/ck8dpqbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="svsuljcxx"/><path clip-rule="evenodd" class="ck8dpqbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:success-12" {...props}></Icon>
