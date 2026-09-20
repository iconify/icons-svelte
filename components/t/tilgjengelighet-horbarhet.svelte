<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk1vdrbbx.css';
import '../../css/v/v038z-9jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk1vdrbbx"/><path class="v038z-9jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:tilgjengelighet-horbarhet" {...props}></Icon>
