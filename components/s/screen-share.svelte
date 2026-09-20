<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx1u3jb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mx1u3jb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:screen-share" {...props}></Icon>
