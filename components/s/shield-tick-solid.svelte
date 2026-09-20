<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5wnyc_ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="d5wnyc_ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:shield-tick-solid" {...props}></Icon>
