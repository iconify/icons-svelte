<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvejr9afn.css';
import '../../css/g/g7jnq5bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bvejr9afn"/><path class="g7jnq5bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:semanticui" {...props}></Icon>
