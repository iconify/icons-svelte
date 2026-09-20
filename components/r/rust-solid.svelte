<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8d079btr.css';
import '../../css/r/rxqvapbkk.css';
import '../../css/t/t399ikbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z8d079btr"/><path class="rxqvapbkk"/><path class="t399ikbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rust-solid" {...props}></Icon>
