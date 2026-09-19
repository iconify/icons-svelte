<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgsm5wcff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="sgsm5wcff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:trash" {...props}></Icon>
