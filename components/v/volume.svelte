<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw05-obst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw05-obst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:volume" {...props}></Icon>
