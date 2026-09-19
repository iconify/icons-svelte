<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6xi21cel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x6xi21cel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tag-circle-fill" {...props}></Icon>
