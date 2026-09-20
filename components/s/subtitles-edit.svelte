<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4hhmrs6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4hhmrs6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:subtitles-edit" {...props}></Icon>
