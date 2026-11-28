<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkeq-6-ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkeq-6-ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:train-clock" {...props}></Icon>
