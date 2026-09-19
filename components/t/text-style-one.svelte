<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvbo2fx7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xvbo2fx7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:text-style-one" {...props}></Icon>
