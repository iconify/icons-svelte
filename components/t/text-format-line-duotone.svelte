<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/gwg-y3bus.css';
import '../../css/t/t22me5f7h.css';
import '../../css/o/ost3o95wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwg-y3bus"/><path class="t22me5f7h"/><path class="ost3o95wd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-format-line-duotone" {...props}></Icon>
