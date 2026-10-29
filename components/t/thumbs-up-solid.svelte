<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvto10b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvto10b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thumbs-up-solid" {...props}></Icon>
