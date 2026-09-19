<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtc51tboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1536};
const content = `<path class="rtc51tboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:user-md" {...props}></Icon>
