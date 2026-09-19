<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn-9qwbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fn-9qwbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:yeelight-cube" {...props}></Icon>
