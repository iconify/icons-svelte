<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm9k5wb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":174,"height":53};
const content = `<path class="qm9k5wb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vellum" {...props}></Icon>
