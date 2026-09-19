<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz993v_go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz993v_go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-lock" {...props}></Icon>
