<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu0re_lux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu0re_lux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transfer-vertical" {...props}></Icon>
