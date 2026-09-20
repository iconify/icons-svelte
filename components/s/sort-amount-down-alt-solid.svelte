<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csb45tgkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="csb45tgkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-amount-down-alt-solid" {...props}></Icon>
