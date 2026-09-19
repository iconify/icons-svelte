<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amcaz4b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="amcaz4b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:waxing-gibbous-moon-symbol" {...props}></Icon>
