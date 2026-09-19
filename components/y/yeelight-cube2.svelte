<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm-tuvb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm-tuvb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:yeelight-cube2" {...props}></Icon>
