<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmx9skinh.css';
import '../../css/x/xc4hi7hnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmx9skinh"/><path class="xc4hi7hnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-grumpy" {...props}></Icon>
