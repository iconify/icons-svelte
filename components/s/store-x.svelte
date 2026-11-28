<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvxll9bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvxll9bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:store-x" {...props}></Icon>
