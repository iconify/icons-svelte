<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qh2weobgl.css';
import '../../css/b/bp33wodtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qh2weobgl"/><path class="bp33wodtm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:user-add-plus-flat" {...props}></Icon>
