<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grr2lyqiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grr2lyqiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:uservoice" {...props}></Icon>
