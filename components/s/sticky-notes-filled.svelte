<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tugoukqgy.css';
import '../../css/s/sc-v4kmjp.css';
import '../../css/k/kqvg6317g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tugoukqgy"/><path clip-rule="evenodd" class="sc-v4kmjp"/><path class="kqvg6317g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticky-notes-filled" {...props}></Icon>
