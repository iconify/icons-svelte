<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gheq95bra.css';
import '../../css/x/xk9zeubkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gheq95bra"/><path class="xk9zeubkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:settings-2-outline" {...props}></Icon>
