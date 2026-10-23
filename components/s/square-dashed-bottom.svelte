<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iebl_j8zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iebl_j8zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-dashed-bottom" {...props}></Icon>
