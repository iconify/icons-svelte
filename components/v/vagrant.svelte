<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu4ihg-sz.css';
import '../../css/x/x3brn5b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fu4ihg-sz"/><path class="x3brn5b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vagrant" {...props}></Icon>
