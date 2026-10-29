<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmpy0gb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmpy0gb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-dashed-solid" {...props}></Icon>
