<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2m4cqbmb.css';
import '../../css/f/f2vy__bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2m4cqbmb"/><path class="f2vy__bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trash-off-filled" {...props}></Icon>
