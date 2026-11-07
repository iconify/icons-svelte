<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/f/fp37m2bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path clip-rule="evenodd" class="fp37m2bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-right-square-bold-duotone" {...props}></Icon>
