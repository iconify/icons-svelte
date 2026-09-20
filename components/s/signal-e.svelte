<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npinuub4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npinuub4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:signal-e" {...props}></Icon>
