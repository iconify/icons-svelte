<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaab5ibre.css';
import '../../css/c/c1rlgi-9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":420,"height":419};
const content = `<circle paint-order="stroke fill markers" class="qaab5ibre"/><path class="c1rlgi-9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:watchman" {...props}></Icon>
