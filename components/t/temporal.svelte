<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjn2c_7rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjn2c_7rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:temporal" {...props}></Icon>
