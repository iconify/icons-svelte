<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapg4nbep.css';
import '../../css/r/rk99s4m6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qapg4nbep"/><path class="rk99s4m6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:spx" {...props}></Icon>
