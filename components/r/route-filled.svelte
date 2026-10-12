<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqn_vacfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqn_vacfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:route-filled" {...props}></Icon>
