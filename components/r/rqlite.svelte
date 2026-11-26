<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3r9tub9u.css';
import '../../css/k/k78qywbzi.css';
import '../../css/d/dp-xfwbez.css';
import '../../css/d/dh01pubcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a3r9tub9u"/><path class="k78qywbzi"/><path class="dp-xfwbez"/><path class="dh01pubcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rqlite" {...props}></Icon>
