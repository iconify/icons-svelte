<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyja5evvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyja5evvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:won" {...props}></Icon>
