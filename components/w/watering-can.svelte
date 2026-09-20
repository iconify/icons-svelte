<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haj2_seqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="haj2_seqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:watering-can" {...props}></Icon>
