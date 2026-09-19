<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukj9idxuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukj9idxuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-pi-light" {...props}></Icon>
