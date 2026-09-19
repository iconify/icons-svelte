<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-el4czwj.css';
import '../../css/b/bp4q0jolu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<circle class="u-el4czwj"/><path class="bp4q0jolu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-midpoint" {...props}></Icon>
