<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egj1p0bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="egj1p0bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:star-o" {...props}></Icon>
