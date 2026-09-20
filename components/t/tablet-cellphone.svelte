<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1q02n5hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1q02n5hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tablet-cellphone" {...props}></Icon>
