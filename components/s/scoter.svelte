<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyuwcobdj.css';
import '../../css/n/n6xp_z95z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyuwcobdj"/><path class="n6xp_z95z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:scoter" {...props}></Icon>
