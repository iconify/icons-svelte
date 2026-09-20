<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg4rtebgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg4rtebgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:zap-sharp-fill" {...props}></Icon>
