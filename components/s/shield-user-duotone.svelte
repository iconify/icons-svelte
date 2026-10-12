<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c413qfd-x.css';
import '../../css/k/kdck7fbvx.css';
import '../../css/g/g3fmatb8b.css';
import '../../css/r/rgggbcbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="c413qfd-x"/><path class="kdck7fbvx"/><path class="g3fmatb8b"/><path class="rgggbcbui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-user-duotone" {...props}></Icon>
