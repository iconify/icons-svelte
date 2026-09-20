<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aks-r-baq.css';
import '../../css/q/qm97rya6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aks-r-baq"/><path class="qm97rya6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:socks" {...props}></Icon>
