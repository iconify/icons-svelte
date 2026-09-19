<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwys74b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":766};
const content = `<path class="mwys74b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:zoomin" {...props}></Icon>
