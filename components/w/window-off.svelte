<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsci9sbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsci9sbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:window-off" {...props}></Icon>
