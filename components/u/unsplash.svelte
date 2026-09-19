<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qza-7dbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qza-7dbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:unsplash" {...props}></Icon>
