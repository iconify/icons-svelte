<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy-dcnr9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy-dcnr9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:workflow-exit-door-bold" {...props}></Icon>
