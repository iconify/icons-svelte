<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7kidxw6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7kidxw6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:target" {...props}></Icon>
