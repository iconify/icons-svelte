<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsb9y4bou.css';
import '../../css/g/gwtyn9bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dsb9y4bou"/><path class="gwtyn9bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:worklenz" {...props}></Icon>
