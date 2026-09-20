<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y6foxtgri.css';
import '../../css/v/vjw4_4bem.css';
import '../../css/o/orb04qb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y6foxtgri"/><path class="vjw4_4bem"/><path class="orb04qb6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:video-game-controller-team" {...props}></Icon>
