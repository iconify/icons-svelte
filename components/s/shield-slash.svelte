<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdzl840ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdzl840ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-slash" {...props}></Icon>
