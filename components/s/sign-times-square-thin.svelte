<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd_qvjb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd_qvjb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-times-square-thin" {...props}></Icon>
