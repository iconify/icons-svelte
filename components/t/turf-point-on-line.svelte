<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg9h-rbgi.css';
import '../../css/h/hnwh_8bzy.css';
import '../../css/g/gqrul3baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jg9h-rbgi"/><circle class="hnwh_8bzy"/><path class="gqrul3baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-point-on-line" {...props}></Icon>
