<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8xbvrbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8xbvrbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:star-half-outline" {...props}></Icon>
