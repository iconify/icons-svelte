<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3cygzbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="o3cygzbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:swift" {...props}></Icon>
