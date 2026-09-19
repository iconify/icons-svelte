<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0mn9fwnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0mn9fwnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shower" {...props}></Icon>
