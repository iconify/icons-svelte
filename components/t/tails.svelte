<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od5se8z1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od5se8z1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tails" {...props}></Icon>
