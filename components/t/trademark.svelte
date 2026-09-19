<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-a_ppb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="m-a_ppb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:trademark" {...props}></Icon>
