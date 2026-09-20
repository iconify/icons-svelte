<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jav1g1szf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jav1g1szf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection-mutliple" {...props}></Icon>
