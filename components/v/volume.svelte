<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gubc_nt6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gubc_nt6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:volume" {...props}></Icon>
