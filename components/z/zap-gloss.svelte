<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0u94epby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0u94epby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zap-gloss" {...props}></Icon>
