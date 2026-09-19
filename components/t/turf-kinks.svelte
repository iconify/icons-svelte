<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/togxi8l0i.css';
import '../../css/c/c4i61rb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="togxi8l0i"/><circle class="c4i61rb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-kinks" {...props}></Icon>
