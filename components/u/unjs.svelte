<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzb3omb7i.css';
import '../../css/x/x9dxbgztj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":60,"height":60};
const content = `<path class="tzb3omb7i"/><path class="x9dxbgztj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unjs" {...props}></Icon>
