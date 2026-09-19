<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehem8xbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehem8xbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:satoshi-v2-outline" {...props}></Icon>
