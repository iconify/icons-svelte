<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmu5l1qta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmu5l1qta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wind-solid" {...props}></Icon>
