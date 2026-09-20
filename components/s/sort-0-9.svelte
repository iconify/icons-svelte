<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbrp83znd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbrp83znd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-0-9" {...props}></Icon>
