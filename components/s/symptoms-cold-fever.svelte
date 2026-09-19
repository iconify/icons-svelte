<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db_fracjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db_fracjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:symptoms-cold-fever" {...props}></Icon>
