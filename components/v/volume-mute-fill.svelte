<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6q6prwfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6q6prwfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:volume-mute-fill" {...props}></Icon>
