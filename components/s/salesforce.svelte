<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjam85b1s.css';
import '../../css/w/wuycig-pg.css';
import '../../css/v/v6x11jg6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":999,"height":699.242,"left":0.5,"top":0.5};
const content = `<path class="rjam85b1s"/><path class="wuycig-pg"/><path class="v6x11jg6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:salesforce" {...props}></Icon>
