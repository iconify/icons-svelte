<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4q_dhbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f4q_dhbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:twitch" {...props}></Icon>
