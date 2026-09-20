<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s10i8bb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s10i8bb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:youtube-fill-24" {...props}></Icon>
