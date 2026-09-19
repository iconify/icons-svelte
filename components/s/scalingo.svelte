<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9_6bmb7k.css';
import '../../css/e/ebvmgs0jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c9_6bmb7k"/><path class="ebvmgs0jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:scalingo" {...props}></Icon>
