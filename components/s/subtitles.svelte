<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kccyurodz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="kccyurodz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:subtitles" {...props}></Icon>
