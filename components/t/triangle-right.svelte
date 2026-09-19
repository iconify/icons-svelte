<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dksa10bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dksa10bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:triangle-right" {...props}></Icon>
