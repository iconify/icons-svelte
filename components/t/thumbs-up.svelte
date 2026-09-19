<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvllrb36k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvllrb36k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:thumbs-up" {...props}></Icon>
