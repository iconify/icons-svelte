<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8y2vtl5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8y2vtl5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wifi-alert" {...props}></Icon>
