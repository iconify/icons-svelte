<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klfze56cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klfze56cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:table-view" {...props}></Icon>
