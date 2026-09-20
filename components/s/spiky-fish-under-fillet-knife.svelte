<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck-872bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ck-872bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spiky-fish-under-fillet-knife" {...props}></Icon>
