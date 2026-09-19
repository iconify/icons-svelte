<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm0y8yomm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hm0y8yomm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:signpost" {...props}></Icon>
