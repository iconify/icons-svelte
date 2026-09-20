<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/citx28jbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="citx28jbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:startdotgg" {...props}></Icon>
