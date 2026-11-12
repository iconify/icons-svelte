<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csj5fll6c.css';
import '../../css/y/y_bc29brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="csj5fll6c"/><path class="y_bc29brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wardrowbe-dark" {...props}></Icon>
