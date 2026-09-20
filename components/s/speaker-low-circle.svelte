<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iscyndbhr.css';
import '../../css/i/iju8bibep.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="iscyndbhr"/><path class="iju8bibep"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:speaker-low-circle" {...props}></Icon>
