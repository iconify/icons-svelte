<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wauk5sbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wauk5sbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:user-check" {...props}></Icon>
