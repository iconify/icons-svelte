<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unr3xzvqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="unr3xzvqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:turntable2-filled" {...props}></Icon>
