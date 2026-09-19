<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_c0fnb5t.css';
import '../../css/x/xk9zeubkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_c0fnb5t"/><path class="xk9zeubkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:settings-outline" {...props}></Icon>
