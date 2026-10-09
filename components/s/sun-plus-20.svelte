<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8nww4mnw.css';
import '../../css/r/rmh-uhtym.css';
import '../../css/a/aqj0--bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n8nww4mnw"/><path class="rmh-uhtym"/><path class="aqj0--bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-plus-20" {...props}></Icon>
