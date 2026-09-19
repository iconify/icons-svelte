<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chp_nybzg.css';
import '../../css/z/ze1bd391g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="chp_nybzg"/><path class="ze1bd391g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:zsh" {...props}></Icon>
