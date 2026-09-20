<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwa2__bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwa2__bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:upload" {...props}></Icon>
