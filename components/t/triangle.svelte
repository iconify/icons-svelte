<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dajk4ccke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dajk4ccke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:triangle" {...props}></Icon>
