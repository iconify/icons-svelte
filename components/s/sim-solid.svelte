<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iywas_9tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="iywas_9tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sim-solid" {...props}></Icon>
