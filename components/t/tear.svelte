<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/als-o4ltu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="als-o4ltu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:tear" {...props}></Icon>
