<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1byepbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="s1byepbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:venus" {...props}></Icon>
