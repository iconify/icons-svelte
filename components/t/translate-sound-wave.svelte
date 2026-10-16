<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye0liacoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye0liacoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:translate-sound-wave" {...props}></Icon>
