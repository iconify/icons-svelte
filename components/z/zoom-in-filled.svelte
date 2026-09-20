<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gza2r1ukg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gza2r1ukg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-in-filled" {...props}></Icon>
