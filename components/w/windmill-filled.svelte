<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_6fu2b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_6fu2b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:windmill-filled" {...props}></Icon>
