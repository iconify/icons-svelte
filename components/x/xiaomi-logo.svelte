<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm99fnsmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm99fnsmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:xiaomi-logo" {...props}></Icon>
