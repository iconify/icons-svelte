<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcoqksbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcoqksbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:university" {...props}></Icon>
