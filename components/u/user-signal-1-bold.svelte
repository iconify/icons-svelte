<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf5sz9i8w.css';
import '../../css/l/l5sm_m-zm.css';
import '../../css/g/gdubncbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf5sz9i8w"/><path class="l5sm_m-zm"/><path class="gdubncbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:user-signal-1-bold" {...props}></Icon>
