<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfpnljbdr.css';
import '../../css/r/rmabd8pvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfpnljbdr"/><path clip-rule="evenodd" class="rmabd8pvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:settings-24" {...props}></Icon>
