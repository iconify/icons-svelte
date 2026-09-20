<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebbfibbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebbfibbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stat" {...props}></Icon>
