<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxb4yw5qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxb4yw5qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:step-backward-alt" {...props}></Icon>
