<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj1lh6o2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj1lh6o2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-exclamation-filled" {...props}></Icon>
