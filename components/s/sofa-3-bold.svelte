<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2c4dccfz.css';
import '../../css/r/rm7ga8nok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2c4dccfz"/><path class="rm7ga8nok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-3-bold" {...props}></Icon>
