<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynah5zt6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynah5zt6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-number-3-filled" {...props}></Icon>
