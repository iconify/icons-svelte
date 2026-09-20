<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn5kgc44z.css';
import '../../css/k/kzsbztbag.css';
import '../../css/a/axjbu5tsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jn5kgc44z"/><path class="kzsbztbag"/><path class="axjbu5tsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:uml-light" {...props}></Icon>
