<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i33xfsc3n.css';
import '../../css/k/k3w3y09sg.css';
import '../../css/u/u1fsh4agr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i33xfsc3n"/><path class="k3w3y09sg"/><path class="u1fsh4agr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stargazing-20" {...props}></Icon>
