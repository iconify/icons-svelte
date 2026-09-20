<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcqscqbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcqscqbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:weight-filled" {...props}></Icon>
