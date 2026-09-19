<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni1s3p96w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ni1s3p96w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:secret-book" {...props}></Icon>
