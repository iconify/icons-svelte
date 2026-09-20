<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0vmu_bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0vmu_bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:trash-x-filled" {...props}></Icon>
