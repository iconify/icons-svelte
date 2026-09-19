<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psdu6ykly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psdu6ykly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:volume-off-filled" {...props}></Icon>
