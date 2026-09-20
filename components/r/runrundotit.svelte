<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv79-2bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv79-2bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:runrundotit" {...props}></Icon>
