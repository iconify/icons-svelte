<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw6hy-k3l.css';
import '../../css/q/q7cxp6bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pw6hy-k3l"/><path clip-rule="evenodd" class="q7cxp6bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:safari-solid" {...props}></Icon>
