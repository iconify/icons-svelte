<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtbki-bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="wtbki-bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:temperature-half" {...props}></Icon>
