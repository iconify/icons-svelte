<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd1lu708s.css';
import '../../css/g/gmbi57b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sd1lu708s"/><path class="gmbi57b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stackblitz-wordmark" {...props}></Icon>
