<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2-x1gb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2-x1gb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-pan-filled" {...props}></Icon>
