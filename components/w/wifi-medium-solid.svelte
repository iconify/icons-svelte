<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm_nfg0bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm_nfg0bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-medium-solid" {...props}></Icon>
