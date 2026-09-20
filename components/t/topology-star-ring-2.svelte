<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq5aii1hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq5aii1hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-star-ring-2" {...props}></Icon>
