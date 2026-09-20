<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9-rvbopt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9-rvbopt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-forward-fill" {...props}></Icon>
