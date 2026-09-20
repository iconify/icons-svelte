<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n69hrbuma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n69hrbuma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:social-distancing" {...props}></Icon>
