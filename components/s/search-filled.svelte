<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc0zatbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc0zatbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-filled" {...props}></Icon>
