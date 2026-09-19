<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk_g8w7ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="fk_g8w7ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:router" {...props}></Icon>
