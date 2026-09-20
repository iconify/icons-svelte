<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5egc3bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5egc3bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:safe-square-outline" {...props}></Icon>
