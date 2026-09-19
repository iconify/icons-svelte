<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clar4rilh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clar4rilh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sparkles-alt-filled" {...props}></Icon>
