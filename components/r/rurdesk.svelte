<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1e7ksb2s.css';
import '../../css/r/r2xn4m3wh.css';
import '../../css/y/yq64yzyqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c1e7ksb2s"/><path class="r2xn4m3wh"/><circle class="yq64yzyqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rurdesk" {...props}></Icon>
