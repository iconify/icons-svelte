<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iocxmprqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iocxmprqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signpost-fill" {...props}></Icon>
