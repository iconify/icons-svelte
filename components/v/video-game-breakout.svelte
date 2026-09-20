<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/us3uf0o7r.css';
import '../../css/f/f5_w3wu9l.css';
import '../../css/l/libu0wbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="us3uf0o7r"/><path class="f5_w3wu9l"/><path class="libu0wbyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:video-game-breakout" {...props}></Icon>
