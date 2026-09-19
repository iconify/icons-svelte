<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9an2g__w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j9an2g__w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:save-to-mobile" {...props}></Icon>
