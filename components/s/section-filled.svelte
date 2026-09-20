<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fary13bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fary13bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:section-filled" {...props}></Icon>
