<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hofj0bbhg.css';
import '../../css/s/scumg8b4j.css';
import '../../css/k/ka-owj1yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hofj0bbhg"/><path class="scumg8b4j"/><path clip-rule="evenodd" class="ka-owj1yr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:thumbtack-list-duotone" {...props}></Icon>
