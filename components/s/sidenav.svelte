<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs47uhblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zs47uhblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sidenav" {...props}></Icon>
