<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiob59blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiob59blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:yeelight-desklamp" {...props}></Icon>
