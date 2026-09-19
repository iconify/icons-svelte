<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yedb5g6ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yedb5g6ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vox" {...props}></Icon>
