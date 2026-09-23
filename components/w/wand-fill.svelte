<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2a2i4c6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2a2i4c6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wand-fill" {...props}></Icon>
