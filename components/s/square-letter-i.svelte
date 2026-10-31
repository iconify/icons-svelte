<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arepo8bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arepo8bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-letter-i" {...props}></Icon>
