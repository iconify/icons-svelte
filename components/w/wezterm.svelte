<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k80un7zxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k80un7zxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wezterm" {...props}></Icon>
