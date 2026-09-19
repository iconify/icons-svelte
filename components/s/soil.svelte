<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dty-esq6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dty-esq6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:soil" {...props}></Icon>
