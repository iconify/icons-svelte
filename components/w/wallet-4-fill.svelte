<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l55_2bcdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l55_2bcdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-4-fill" {...props}></Icon>
