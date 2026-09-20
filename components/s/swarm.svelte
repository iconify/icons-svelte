<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o79d4wzpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o79d4wzpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:swarm" {...props}></Icon>
