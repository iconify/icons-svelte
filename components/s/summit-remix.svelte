<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm2gtmtka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm2gtmtka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:summit-remix" {...props}></Icon>
