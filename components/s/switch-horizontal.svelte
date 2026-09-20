<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol2ps3w7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol2ps3w7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:switch-horizontal" {...props}></Icon>
