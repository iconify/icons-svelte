<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xngkwz6zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xngkwz6zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trophy-solid" {...props}></Icon>
