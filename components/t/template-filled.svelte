<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvgxz_baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvgxz_baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:template-filled" {...props}></Icon>
