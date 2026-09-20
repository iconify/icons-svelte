<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v02mowbow.css';
import '../../css/c/c2nbybb8g.css';
import '../../css/x/xj22oqcto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v02mowbow"/><circle class="c2nbybb8g"/><rect class="xj22oqcto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rsshub" {...props}></Icon>
