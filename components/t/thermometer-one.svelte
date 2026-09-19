<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thtc11bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="thtc11bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:thermometer-one" {...props}></Icon>
