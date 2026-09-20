<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yian4bcbi.css';
import '../../css/p/phelvmbqn.css';
import '../../css/h/hj977r91q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yian4bcbi"/><path class="phelvmbqn"/><path class="hj977r91q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:screen-tv-flat" {...props}></Icon>
