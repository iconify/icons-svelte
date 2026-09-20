<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg7rb9b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg7rb9b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wash-dry-off" {...props}></Icon>
