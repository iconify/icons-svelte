<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpn8ptbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpn8ptbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-x-sharp" {...props}></Icon>
