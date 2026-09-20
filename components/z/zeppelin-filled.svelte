<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqhj5qbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqhj5qbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zeppelin-filled" {...props}></Icon>
