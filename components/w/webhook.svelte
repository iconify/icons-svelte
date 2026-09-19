<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-go91ypk.css';
import '../../css/m/mkwx26bok.css';
import '../../css/f/fv05gfbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n-go91ypk"/><path class="mkwx26bok"/><path class="fv05gfbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:webhook" {...props}></Icon>
