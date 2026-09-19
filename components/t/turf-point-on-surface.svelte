<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbv4wpb-c.css';
import '../../css/c/csr9vodhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zbv4wpb-c"/><circle class="csr9vodhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-point-on-surface" {...props}></Icon>
