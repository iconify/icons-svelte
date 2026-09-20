<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo282mbbg.css';
import '../../css/t/tj13mnmfk.css';
import '../../css/v/v8bzv4b3x.css';
import '../../css/y/yry9ecckx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo282mbbg"/><path clip-rule="evenodd" class="tj13mnmfk"/><path class="v8bzv4b3x"/><path clip-rule="evenodd" class="yry9ecckx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:undead" {...props}></Icon>
