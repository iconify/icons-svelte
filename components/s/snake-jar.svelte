<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp26bdkej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp26bdkej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snake-jar" {...props}></Icon>
