<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7yaui2em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7yaui2em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:volume" {...props}></Icon>
