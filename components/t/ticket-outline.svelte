<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6-tw7fdl.css';
import '../../css/u/u57zsmbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6-tw7fdl"/><path class="u57zsmbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ticket-outline" {...props}></Icon>
