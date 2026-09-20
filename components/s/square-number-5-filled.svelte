<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6kq_-bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6kq_-bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-number-5-filled" {...props}></Icon>
