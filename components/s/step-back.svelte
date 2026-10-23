<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh9x1_b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh9x1_b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:step-back" {...props}></Icon>
