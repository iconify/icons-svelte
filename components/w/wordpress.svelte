<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ng3juba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ng3juba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:wordpress" {...props}></Icon>
