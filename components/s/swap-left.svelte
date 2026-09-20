<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8-frc3ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t8-frc3ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:swap-left" {...props}></Icon>
