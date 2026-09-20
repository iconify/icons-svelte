<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aekdueaqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aekdueaqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-off-solid" {...props}></Icon>
