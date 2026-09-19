<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amwc6obxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amwc6obxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:tablet-button" {...props}></Icon>
