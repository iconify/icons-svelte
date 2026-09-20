<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua22syaej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ua22syaej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storyden-dark" {...props}></Icon>
