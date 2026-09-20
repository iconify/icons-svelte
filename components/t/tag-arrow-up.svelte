<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsyd4bbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsyd4bbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-arrow-up" {...props}></Icon>
