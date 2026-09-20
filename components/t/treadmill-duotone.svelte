<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mkih2u7bz.css';
import '../../css/e/e9aqe8bfl.css';
import '../../css/g/gqcy9hz5b.css';
import '../../css/i/is81_p17l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mkih2u7bz"/><path clip-rule="evenodd" class="e9aqe8bfl"/><path class="gqcy9hz5b"/><path class="is81_p17l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:treadmill-duotone" {...props}></Icon>
