<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3tybgbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3tybgbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scanner2" {...props}></Icon>
