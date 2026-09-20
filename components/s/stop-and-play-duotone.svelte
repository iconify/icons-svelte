<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unc2embyj.css';
import '../../css/j/j2l72bb1a.css';
import '../../css/k/kv5hm5h9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="unc2embyj"><path class="j2l72bb1a"/><path class="kv5hm5h9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:stop-and-play-duotone" {...props}></Icon>
