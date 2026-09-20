<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efl1rxmzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="efl1rxmzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wolf-head" {...props}></Icon>
