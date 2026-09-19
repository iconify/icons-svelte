<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahbt8qg5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ahbt8qg5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:stop-btn-fill" {...props}></Icon>
