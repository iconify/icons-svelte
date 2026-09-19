<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r51k3lv5c.css';
import '../../css/v/v_3i9wmxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r51k3lv5c"/><path class="v_3i9wmxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:windows-filled" {...props}></Icon>
