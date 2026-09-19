<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-7bhxbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-7bhxbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:upload" {...props}></Icon>
