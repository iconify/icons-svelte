<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpqb_3bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wpqb_3bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:spanner" {...props}></Icon>
