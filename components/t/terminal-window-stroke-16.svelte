<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kotd2wpwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kotd2wpwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-window-stroke-16" {...props}></Icon>
