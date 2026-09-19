<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6__l5bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6__l5bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:train-filled" {...props}></Icon>
