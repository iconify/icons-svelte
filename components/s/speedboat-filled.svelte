<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2h7nfjar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2h7nfjar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:speedboat-filled" {...props}></Icon>
