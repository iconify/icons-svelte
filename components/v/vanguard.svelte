<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbkebpbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbkebpbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vanguard" {...props}></Icon>
