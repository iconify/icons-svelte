<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j068v3bze.css';
import '../../css/n/nl66y9men.css';
import '../../css/w/wjwwm-bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j068v3bze"/><path class="nl66y9men wm-a"/><path class="wjwwm-bhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:voicemail-duo" {...props}></Icon>
