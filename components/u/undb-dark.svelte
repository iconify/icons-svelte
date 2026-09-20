<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv02buttj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tv02buttj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:undb-dark" {...props}></Icon>
