<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3cll2epf.css';
import '../../css/w/w-wp2mbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u3cll2epf"/><path class="w-wp2mbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:typescript" {...props}></Icon>
