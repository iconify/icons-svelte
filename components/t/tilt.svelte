<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa2yz5sit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":470,"height":512};
const content = `<path class="wa2yz5sit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:tilt" {...props}></Icon>
