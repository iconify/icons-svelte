<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdv-4ebbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdv-4ebbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:yak" {...props}></Icon>
