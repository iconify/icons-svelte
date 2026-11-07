<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0hskbc8u.css';
import '../../css/a/af2lrdbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0hskbc8u"/><path class="af2lrdbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-3-bold-duotone" {...props}></Icon>
