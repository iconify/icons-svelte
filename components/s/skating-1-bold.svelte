<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmubjfrve.css';
import '../../css/o/oiva0jb0e.css';
import '../../css/g/ghoccmbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmubjfrve"/><path class="oiva0jb0e"/><path class="ghoccmbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:skating-1-bold" {...props}></Icon>
