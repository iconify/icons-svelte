<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwbwp2bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwbwp2bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sun" {...props}></Icon>
