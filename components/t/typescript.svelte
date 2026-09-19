<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/essr0js1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="essr0js1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:typescript" {...props}></Icon>
