<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtc8mk_md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtc8mk_md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:slash-dot-logo" {...props}></Icon>
