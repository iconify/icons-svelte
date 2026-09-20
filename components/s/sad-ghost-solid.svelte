<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqfe0qbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqfe0qbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sad-ghost-solid" {...props}></Icon>
