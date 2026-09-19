<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1nukqbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1nukqbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tube-lights" {...props}></Icon>
