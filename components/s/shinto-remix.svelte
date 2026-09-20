<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt4rnojpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mt4rnojpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shinto-remix" {...props}></Icon>
