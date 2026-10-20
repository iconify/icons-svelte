<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md-zhkn3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="md-zhkn3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scanfile" {...props}></Icon>
