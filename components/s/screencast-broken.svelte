<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mnp-46y7d.css';
import '../../css/v/v4tckp_mx.css';
import '../../css/d/dxz_62g8x.css';
import '../../css/u/uzj9wplpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mnp-46y7d"/><path class="v4tckp_mx"/><path class="dxz_62g8x"/><path class="uzj9wplpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screencast-broken" {...props}></Icon>
