<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhzhsy8bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhzhsy8bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:twitch" {...props}></Icon>
