<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta36lgbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ta36lgbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-minus-20" {...props}></Icon>
