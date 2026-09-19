<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_qj26bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="u_qj26bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tent-arrow-turn-left" {...props}></Icon>
