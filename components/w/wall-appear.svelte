<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2c24ph4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2c24ph4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-appear" {...props}></Icon>
