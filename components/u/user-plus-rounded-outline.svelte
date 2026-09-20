<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc8l53b6q.css';
import '../../css/y/y0wtcrqbx.css';
import '../../css/x/x0r9zqw6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mc8l53b6q"/><path class="y0wtcrqbx"/><path clip-rule="evenodd" class="x0r9zqw6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-plus-rounded-outline" {...props}></Icon>
