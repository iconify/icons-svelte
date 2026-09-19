<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjaiwl-7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mjaiwl-7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:timeselect" {...props}></Icon>
