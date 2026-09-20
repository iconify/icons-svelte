<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uas_wub4v.css';
import '../../css/h/hoehcpaco.css';
import '../../css/n/n4j0dbcil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uas_wub4v"/><path class="hoehcpaco"/><path class="n4j0dbcil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:window-maximize" {...props}></Icon>
