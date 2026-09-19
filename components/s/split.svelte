<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhd3tibki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhd3tibki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:split" {...props}></Icon>
