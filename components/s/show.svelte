<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caytelnwd.css';
import '../../css/f/f31x6qb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caytelnwd"/><path class="f31x6qb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:show" {...props}></Icon>
