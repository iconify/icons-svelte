<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb2c95t9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb2c95t9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:saudi-riyal" {...props}></Icon>
