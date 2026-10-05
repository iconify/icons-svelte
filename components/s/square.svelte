<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_eia8bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_eia8bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:square" {...props}></Icon>
