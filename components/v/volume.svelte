<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx1wr_bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx1wr_bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:volume" {...props}></Icon>
