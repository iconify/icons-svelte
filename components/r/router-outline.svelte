<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqpn2xbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fqpn2xbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:router-outline" {...props}></Icon>
