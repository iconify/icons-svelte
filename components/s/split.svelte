<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha1ngc8fk.css';
import '../../css/v/vrz9w3bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ha1ngc8fk"/><path class="vrz9w3bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:split" {...props}></Icon>
