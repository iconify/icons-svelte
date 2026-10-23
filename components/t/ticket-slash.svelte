<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2m8x4baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2m8x4baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ticket-slash" {...props}></Icon>
