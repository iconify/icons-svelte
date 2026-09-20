<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bap5c6bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bap5c6bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:volume-equal" {...props}></Icon>
