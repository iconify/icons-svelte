<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko0p_sozw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ko0p_sozw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:rss" {...props}></Icon>
