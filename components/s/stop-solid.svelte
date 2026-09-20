<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlvpz0bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlvpz0bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:stop-solid" {...props}></Icon>
