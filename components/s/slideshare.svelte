<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/badz66hkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="badz66hkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:slideshare" {...props}></Icon>
