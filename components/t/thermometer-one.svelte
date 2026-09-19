<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9osicbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s9osicbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:thermometer-one" {...props}></Icon>
