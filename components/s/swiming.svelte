<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m912t5v7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m912t5v7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:swiming" {...props}></Icon>
