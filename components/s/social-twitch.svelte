<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx8sdnbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xx8sdnbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-twitch" {...props}></Icon>
