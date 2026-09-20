<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t60iywbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t60iywbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transaction-euro" {...props}></Icon>
