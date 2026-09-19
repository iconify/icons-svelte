<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exophsjeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="exophsjeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-arrow-down-fill" {...props}></Icon>
