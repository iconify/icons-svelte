<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ah8go7bph.css';
import '../../css/u/uhv6q9tdz.css';
import '../../css/n/nu1ky11cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ah8go7bph"/><path class="uhv6q9tdz"/><path class="nu1ky11cm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:triangle-alert-duotone" {...props}></Icon>
