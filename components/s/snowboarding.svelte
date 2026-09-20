<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqy_hqb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jqy_hqb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:snowboarding" {...props}></Icon>
