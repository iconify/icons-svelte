<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7n7f3ipf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7n7f3ipf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:vimeo-fill" {...props}></Icon>
