<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c625vx81f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c625vx81f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speedometer" {...props}></Icon>
