<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h07yl7b2h.css';
import '../../css/m/m2bvsebeo.css';
import '../../css/z/z7i3a0bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":23};
const content = `<g class="ft5dv1b6b"><path class="h07yl7b2h"/><path class="m2bvsebeo"/><path class="z7i3a0bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unleash" {...props}></Icon>
