<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mti05vejb.css';
import '../../css/q/qxq52ip6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mti05vejb"/><path class="qxq52ip6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:tooth" {...props}></Icon>
