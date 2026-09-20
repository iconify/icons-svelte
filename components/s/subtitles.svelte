<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhl3a5t6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhl3a5t6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:subtitles" {...props}></Icon>
