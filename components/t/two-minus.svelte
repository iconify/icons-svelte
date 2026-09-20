<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziiaqvbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ziiaqvbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-minus" {...props}></Icon>
