<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta5p_muku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ta5p_muku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:screen-16" {...props}></Icon>
