<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/octq69bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="octq69bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:square-11" {...props}></Icon>
