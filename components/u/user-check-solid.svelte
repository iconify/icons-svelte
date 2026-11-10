<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re0-0ibvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="re0-0ibvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:user-check-solid" {...props}></Icon>
