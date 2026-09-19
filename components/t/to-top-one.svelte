<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otm15eu5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="otm15eu5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:to-top-one" {...props}></Icon>
