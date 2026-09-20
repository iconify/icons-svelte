<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb5foabvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yb5foabvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:twenty-four-hour-support-filled" {...props}></Icon>
