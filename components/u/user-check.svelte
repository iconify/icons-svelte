<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecobcdb3u.css';
import '../../css/t/tgdfm4b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ecobcdb3u"/><path class="tgdfm4b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:user-check" {...props}></Icon>
