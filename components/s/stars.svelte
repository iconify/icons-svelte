<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5mdiyb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5mdiyb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:stars" {...props}></Icon>
