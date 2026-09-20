<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n02_ubbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n02_ubbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:truck" {...props}></Icon>
