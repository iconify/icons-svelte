<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4c48d6gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4c48d6gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-online-outline" {...props}></Icon>
