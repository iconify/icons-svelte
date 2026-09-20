<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smvh-7b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smvh-7b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sunset-filled" {...props}></Icon>
