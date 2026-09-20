<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbn7mm_ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbn7mm_ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-code" {...props}></Icon>
