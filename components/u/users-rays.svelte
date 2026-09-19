<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az9e_ccag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="az9e_ccag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:users-rays" {...props}></Icon>
