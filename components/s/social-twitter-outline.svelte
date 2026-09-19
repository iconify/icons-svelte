<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6pa94bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a6pa94bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-twitter-outline" {...props}></Icon>
