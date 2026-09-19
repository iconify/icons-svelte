<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9lz5abtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9lz5abtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:vertical-merge" {...props}></Icon>
