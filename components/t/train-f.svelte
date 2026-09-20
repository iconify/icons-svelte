<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnzhi8f3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2.5};
const content = `<path class="dnzhi8f3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:train-f" {...props}></Icon>
