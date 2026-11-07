<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyjboy1lu.css';
import '../../css/w/w72z5bcvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyjboy1lu"/><path clip-rule="evenodd" class="w72z5bcvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:thermometer-outline" {...props}></Icon>
