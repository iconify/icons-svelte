<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngv5_zdhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngv5_zdhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:themes" {...props}></Icon>
