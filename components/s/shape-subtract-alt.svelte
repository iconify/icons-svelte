<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slu5h6ecs.css';
import '../../css/f/fu5ar-14p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slu5h6ecs"/><path class="fu5ar-14p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-subtract-alt" {...props}></Icon>
