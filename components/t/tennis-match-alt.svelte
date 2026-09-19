<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mql5pkbnr.css';
import '../../css/p/p68cdpbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mql5pkbnr"/><path class="p68cdpbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:tennis-match-alt" {...props}></Icon>
