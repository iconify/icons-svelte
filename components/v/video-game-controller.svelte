<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mm9o6_bit.css';
import '../../css/z/zzvb92bna.css';
import '../../css/a/avoehdcvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mm9o6_bit"/><path class="zzvb92bna"/><path class="avoehdcvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:video-game-controller" {...props}></Icon>
