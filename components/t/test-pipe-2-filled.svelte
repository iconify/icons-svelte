<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-wa9ac3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-wa9ac3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:test-pipe-2-filled" {...props}></Icon>
