<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pba4racxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pba4racxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sob-fill" {...props}></Icon>
