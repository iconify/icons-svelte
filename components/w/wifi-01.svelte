<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/gwi6sywyz.css';
import '../../css/w/wc19j6nte.css';
import '../../css/l/lza45ccox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwi6sywyz"/><path class="wc19j6nte"/><circle class="lza45ccox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wifi-01" {...props}></Icon>
