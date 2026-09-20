<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkxrg8bqx.css';
import '../../css/v/vcwbpi0dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkxrg8bqx"/><path class="vcwbpi0dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:screencast-filled" {...props}></Icon>
