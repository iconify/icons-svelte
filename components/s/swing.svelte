<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lub9q8fhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lub9q8fhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:swing" {...props}></Icon>
