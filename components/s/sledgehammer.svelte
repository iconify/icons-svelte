<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb2dvngzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rb2dvngzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sledgehammer" {...props}></Icon>
